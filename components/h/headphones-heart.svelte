<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtt60bhpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtt60bhpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:headphones-heart" {...props}></Icon>
