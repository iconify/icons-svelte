<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7924v-lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7924v-lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:basketball" {...props}></Icon>
