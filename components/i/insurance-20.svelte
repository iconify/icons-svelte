<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bitd75egg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bitd75egg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:insurance-20" {...props}></Icon>
