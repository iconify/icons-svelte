<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv1fucc3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hv1fucc3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:anvil-20-bold" {...props}></Icon>
