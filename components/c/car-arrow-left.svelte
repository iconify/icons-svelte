<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hijaslbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hijaslbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-arrow-left" {...props}></Icon>
