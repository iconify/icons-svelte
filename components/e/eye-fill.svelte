<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6k176bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6k176bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:eye-fill" {...props}></Icon>
