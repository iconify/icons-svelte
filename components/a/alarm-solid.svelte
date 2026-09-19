<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2xwd0blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a2xwd0blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:alarm-solid" {...props}></Icon>
