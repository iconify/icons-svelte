<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wef4vzbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wef4vzbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:fluval-fx2-logo" {...props}></Icon>
