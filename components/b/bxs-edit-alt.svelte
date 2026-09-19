<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-cb5xbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-cb5xbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-edit-alt" {...props}></Icon>
