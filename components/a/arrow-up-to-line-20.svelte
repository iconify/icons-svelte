<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c25jzkbsf.css';
import '../../css/w/wy4_yib2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c25jzkbsf"/><path class="wy4_yib2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-to-line-20" {...props}></Icon>
