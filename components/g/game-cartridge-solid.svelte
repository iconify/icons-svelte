<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn-bbdrjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn-bbdrjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:game-cartridge-solid" {...props}></Icon>
