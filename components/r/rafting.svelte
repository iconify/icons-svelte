<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq4vz-hqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="mq4vz-hqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:rafting" {...props}></Icon>
