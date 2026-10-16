<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyuwl4bpc.css';
import '../../css/m/m2qyafbre.css';
import '../../css/z/zi0m9n48q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vyuwl4bpc"/><path class="m2qyafbre"/><path class="zi0m9n48q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:elevator-20" {...props}></Icon>
