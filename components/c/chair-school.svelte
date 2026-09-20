<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn1t_absc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn1t_absc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chair-school" {...props}></Icon>
