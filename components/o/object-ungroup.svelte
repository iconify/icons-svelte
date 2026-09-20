<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp2crcbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp2crcbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:object-ungroup" {...props}></Icon>
