<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcyw8jb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcyw8jb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:3d" {...props}></Icon>
