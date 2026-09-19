<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqi9wvbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqi9wvbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rotate-cw-filled" {...props}></Icon>
