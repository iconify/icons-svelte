<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgmu23bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgmu23bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-zero-box" {...props}></Icon>
