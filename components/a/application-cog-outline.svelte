<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg0unkbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg0unkbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:application-cog-outline" {...props}></Icon>
