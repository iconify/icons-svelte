<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8tb2oehp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8tb2oehp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-arrow-up" {...props}></Icon>
