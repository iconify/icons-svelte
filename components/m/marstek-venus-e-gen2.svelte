<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey-yjdb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey-yjdb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:marstek-venus-e-gen2" {...props}></Icon>
