<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-v3vibll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-v3vibll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clock-gear" {...props}></Icon>
