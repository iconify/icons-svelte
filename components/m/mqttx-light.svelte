<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dio2vj7yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dio2vj7yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mqttx-light" {...props}></Icon>
