<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txei9lbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txei9lbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:org-chart-plus" {...props}></Icon>
