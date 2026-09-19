<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne3jv2bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ne3jv2bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hexagonal" {...props}></Icon>
