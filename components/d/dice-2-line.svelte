<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo1y_5kgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo1y_5kgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dice-2-line" {...props}></Icon>
