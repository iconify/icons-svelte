<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btu8jzbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btu8jzbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:r" {...props}></Icon>
