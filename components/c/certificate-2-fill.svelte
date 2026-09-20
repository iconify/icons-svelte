<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxyz2h5nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxyz2h5nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:certificate-2-fill" {...props}></Icon>
