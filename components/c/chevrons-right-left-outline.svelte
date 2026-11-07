<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmt8ryb3g.css';
import '../../css/u/uijvjtbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmt8ryb3g"/><path class="uijvjtbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-right-left-outline" {...props}></Icon>
