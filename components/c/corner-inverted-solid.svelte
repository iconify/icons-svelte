<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvayf1bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvayf1bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-inverted-solid" {...props}></Icon>
