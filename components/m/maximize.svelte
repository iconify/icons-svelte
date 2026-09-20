<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3_nbdb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3_nbdb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:maximize" {...props}></Icon>
