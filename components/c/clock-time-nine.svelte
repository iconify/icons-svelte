<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzpq5vszr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzpq5vszr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-nine" {...props}></Icon>
