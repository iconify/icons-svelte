<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3wmkebqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3wmkebqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-right-top" {...props}></Icon>
