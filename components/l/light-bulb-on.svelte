<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq0quybsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq0quybsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:light-bulb-on" {...props}></Icon>
