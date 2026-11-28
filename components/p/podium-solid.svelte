<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-oaj0bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-oaj0bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:podium-solid" {...props}></Icon>
