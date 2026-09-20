<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k56efgb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k56efgb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mazanoke-light" {...props}></Icon>
