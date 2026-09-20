<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uszzfzacj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uszzfzacj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fdusd" {...props}></Icon>
