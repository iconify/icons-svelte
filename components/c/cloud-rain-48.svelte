<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a21vn_b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a21vn_b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-rain-48" {...props}></Icon>
