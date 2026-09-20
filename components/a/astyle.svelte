<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqh4l-mdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqh4l-mdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:astyle" {...props}></Icon>
