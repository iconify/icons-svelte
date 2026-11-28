<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxn1b1byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxn1b1byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-long-solid" {...props}></Icon>
