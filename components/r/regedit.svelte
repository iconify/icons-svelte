<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkt9v7b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rkt9v7b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:regedit" {...props}></Icon>
