<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-yg1pedr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-yg1pedr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:phone-solid" {...props}></Icon>
