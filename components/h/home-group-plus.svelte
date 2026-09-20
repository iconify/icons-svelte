<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1dp7r1mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1dp7r1mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:home-group-plus" {...props}></Icon>
