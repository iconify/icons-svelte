<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w44k3_byo.css';
import '../../css/d/di2c6dxli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary w44k3_byo"/><path class="di2c6dxli primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:explosion-duo" {...props}></Icon>
