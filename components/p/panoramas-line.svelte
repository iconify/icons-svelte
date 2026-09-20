<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f22o04bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f22o04bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:panoramas-line" {...props}></Icon>
