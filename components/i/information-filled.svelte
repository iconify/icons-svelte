<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpmw0obfn.css';
import '../../css/e/ehafz-rwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jpmw0obfn"/><path class="ehafz-rwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:information-filled" {...props}></Icon>
