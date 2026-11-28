<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yppvhyjmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yppvhyjmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:maximize-solid" {...props}></Icon>
