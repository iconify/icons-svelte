<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-5eqqj4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-5eqqj4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:light-bulb-alt-2-filled" {...props}></Icon>
