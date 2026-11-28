<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kumx2fb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kumx2fb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:percent" {...props}></Icon>
