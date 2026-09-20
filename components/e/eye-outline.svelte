<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyh8m0cby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kyh8m0cby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eye-outline" {...props}></Icon>
