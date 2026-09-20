<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6hc4yeog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6hc4yeog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:horizontal-down-right-main-light" {...props}></Icon>
