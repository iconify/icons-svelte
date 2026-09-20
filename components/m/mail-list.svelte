<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlzpbdvpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jlzpbdvpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:mail-list" {...props}></Icon>
