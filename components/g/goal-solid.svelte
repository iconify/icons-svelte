<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp4kfgbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp4kfgbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:goal-solid" {...props}></Icon>
