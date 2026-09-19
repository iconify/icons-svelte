<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp7w4tb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp7w4tb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:booth-curtain-solid" {...props}></Icon>
