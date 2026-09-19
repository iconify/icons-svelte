<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_wnf-h8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_wnf-h8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-down-left" {...props}></Icon>
