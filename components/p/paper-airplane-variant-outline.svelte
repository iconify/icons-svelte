<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg9i8bcxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg9i8bcxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paper-airplane-variant-outline" {...props}></Icon>
