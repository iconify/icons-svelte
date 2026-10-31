<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwc177mig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwc177mig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-3x2" {...props}></Icon>
