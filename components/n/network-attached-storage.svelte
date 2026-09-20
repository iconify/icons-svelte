<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1inz6b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1inz6b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:network-attached-storage" {...props}></Icon>
