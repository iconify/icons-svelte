<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hii5eibzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hii5eibzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:opera-outline" {...props}></Icon>
