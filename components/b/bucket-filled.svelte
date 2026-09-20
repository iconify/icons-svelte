<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvt0yqttd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvt0yqttd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bucket-filled" {...props}></Icon>
