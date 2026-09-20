<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2ia15bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2ia15bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bell-fill" {...props}></Icon>
