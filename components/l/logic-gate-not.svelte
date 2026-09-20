<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adyc_d18v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adyc_d18v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:logic-gate-not" {...props}></Icon>
