<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp4e-knky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp4e-knky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cloud-fog-filled" {...props}></Icon>
