<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf_5pebtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf_5pebtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:covid-test" {...props}></Icon>
