<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjry0e9fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjry0e9fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dartboard" {...props}></Icon>
