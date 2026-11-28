<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqqkcsb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqqkcsb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:lock-x" {...props}></Icon>
