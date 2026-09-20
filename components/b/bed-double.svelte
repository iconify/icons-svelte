<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imqjvpsut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imqjvpsut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bed-double" {...props}></Icon>
