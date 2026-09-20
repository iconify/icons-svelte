<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhm8-4bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhm8-4bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:infinity" {...props}></Icon>
