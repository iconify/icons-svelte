<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrh8mub3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrh8mub3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bnb-fill" {...props}></Icon>
