<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auxmv3brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auxmv3brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:receipt-check" {...props}></Icon>
