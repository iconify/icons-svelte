<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmpc50jny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmpc50jny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-settings-outline" {...props}></Icon>
