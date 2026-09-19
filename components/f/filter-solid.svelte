<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gngvdr8bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gngvdr8bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:filter-solid" {...props}></Icon>
