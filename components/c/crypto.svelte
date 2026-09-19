<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adzo3xbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adzo3xbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:crypto" {...props}></Icon>
