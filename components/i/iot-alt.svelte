<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xujvqmbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xujvqmbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:iot-alt" {...props}></Icon>
