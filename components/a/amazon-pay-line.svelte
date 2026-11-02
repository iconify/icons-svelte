<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy7i2epek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy7i2epek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:amazon-pay-line" {...props}></Icon>
