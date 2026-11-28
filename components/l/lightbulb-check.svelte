<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzkbm7b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzkbm7b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:lightbulb-check" {...props}></Icon>
