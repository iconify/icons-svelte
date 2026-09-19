<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kru6wy-1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kru6wy-1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cloudy-night" {...props}></Icon>
