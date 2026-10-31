<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuxp37epe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuxp37epe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:accessibility-fill-round" {...props}></Icon>
