<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7p1x9bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":617,"height":740};
const content = `<path class="a7p1x9bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:evernote" {...props}></Icon>
