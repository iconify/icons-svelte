<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-eq8obkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-eq8obkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:jigsaw-outline" {...props}></Icon>
