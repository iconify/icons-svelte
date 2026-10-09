<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkcnnbb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lkcnnbb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-sun-48" {...props}></Icon>
