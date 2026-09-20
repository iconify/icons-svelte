<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8ffsubai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8ffsubai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-top-left-bold" {...props}></Icon>
