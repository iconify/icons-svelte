<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhtrtmbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhtrtmbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-3-filled" {...props}></Icon>
