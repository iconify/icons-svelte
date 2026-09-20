<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-ttxywqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v-ttxywqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:check-square-solid" {...props}></Icon>
