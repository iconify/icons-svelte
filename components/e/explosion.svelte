<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di2c6dxli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di2c6dxli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:explosion" {...props}></Icon>
