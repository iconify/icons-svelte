<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udlxi0b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udlxi0b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:drone" {...props}></Icon>
