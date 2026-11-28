<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxggxp1wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxggxp1wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:home-alert" {...props}></Icon>
