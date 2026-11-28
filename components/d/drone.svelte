<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwg5rcipv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwg5rcipv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:drone" {...props}></Icon>
