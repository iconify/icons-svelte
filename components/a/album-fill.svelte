<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy-ibbztw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy-ibbztw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:album-fill" {...props}></Icon>
