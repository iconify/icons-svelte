<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkwt02fpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkwt02fpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:rename" {...props}></Icon>
