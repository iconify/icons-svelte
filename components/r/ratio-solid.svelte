<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crofpbcfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crofpbcfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ratio-solid" {...props}></Icon>
