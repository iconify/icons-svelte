<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_ipmzduq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f_ipmzduq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:arrow-left-up" {...props}></Icon>
