<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vppo77fzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vppo77fzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:buliding" {...props}></Icon>
