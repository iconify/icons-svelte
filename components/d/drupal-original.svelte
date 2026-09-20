<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2p-7ubes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="d2p-7ubes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:drupal-original" {...props}></Icon>
