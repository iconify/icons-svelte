<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvt_43blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wvt_43blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:loader-48" {...props}></Icon>
