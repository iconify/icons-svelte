<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o87_bv_-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o87_bv_-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:molecule-co2" {...props}></Icon>
