<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs39h7bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zs39h7bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:animation-minus-outline" {...props}></Icon>
