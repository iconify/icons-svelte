<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n70mjmy2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n70mjmy2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bell-outline" {...props}></Icon>
