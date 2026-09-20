<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd2uyy8hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yd2uyy8hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:lettered-list-20-solid" {...props}></Icon>
