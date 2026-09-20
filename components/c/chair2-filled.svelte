<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmp1uobdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmp1uobdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chair2-filled" {...props}></Icon>
