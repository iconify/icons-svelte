<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsqs2tb6j.css';
import '../../css/w/w1hy86m-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nsqs2tb6j"/><path class="w1hy86m-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-hybrid-48" {...props}></Icon>
