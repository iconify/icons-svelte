<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-e5hhbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="t-e5hhbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:latexmk" {...props}></Icon>
