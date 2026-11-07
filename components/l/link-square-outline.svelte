<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4p_kzgss.css';
import '../../css/y/yz_54e91d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4p_kzgss"/><path class="yz_54e91d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-square-outline" {...props}></Icon>
