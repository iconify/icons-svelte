<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmqh5-yly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmqh5-yly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mail" {...props}></Icon>
