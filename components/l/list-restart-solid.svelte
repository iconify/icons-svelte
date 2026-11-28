<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy462fbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy462fbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-restart-solid" {...props}></Icon>
