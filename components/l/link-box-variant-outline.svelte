<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5x223bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5x223bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:link-box-variant-outline" {...props}></Icon>
