<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq1br_bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq1br_bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-remove" {...props}></Icon>
