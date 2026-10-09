<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e44d_bbpo.css';
import '../../css/n/n4r5wlwiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e44d_bbpo"/><path class="n4r5wlwiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chef-hat-20-bold" {...props}></Icon>
