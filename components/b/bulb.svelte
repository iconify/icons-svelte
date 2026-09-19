<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfz1s_bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfz1s_bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bulb" {...props}></Icon>
