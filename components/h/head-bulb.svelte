<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3hk15psj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3hk15psj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-bulb" {...props}></Icon>
