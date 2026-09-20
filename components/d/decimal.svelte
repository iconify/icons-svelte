<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bljd5e2en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bljd5e2en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:decimal" {...props}></Icon>
