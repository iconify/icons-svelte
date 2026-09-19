<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrsz2bbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrsz2bbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:filter-list" {...props}></Icon>
