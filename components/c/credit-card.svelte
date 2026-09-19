<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcs6_gbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="gcs6_gbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:credit-card" {...props}></Icon>
