<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d55vmqbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d55vmqbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:circle-slice-6" {...props}></Icon>
