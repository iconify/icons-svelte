<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf1i2vbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf1i2vbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:feather-alt" {...props}></Icon>
