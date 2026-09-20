<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3xkn_b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3xkn_b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bullhorn-variant-outline" {...props}></Icon>
