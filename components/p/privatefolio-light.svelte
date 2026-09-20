<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c05xg1fra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c05xg1fra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:privatefolio-light" {...props}></Icon>
