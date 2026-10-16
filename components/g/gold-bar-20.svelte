<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqfs-8dip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zqfs-8dip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gold-bar-20" {...props}></Icon>
