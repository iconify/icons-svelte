<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xklulsq7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xklulsq7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-lock" {...props}></Icon>
