<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrjuz9bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrjuz9bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:heart-off" {...props}></Icon>
