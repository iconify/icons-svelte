<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u19wi-b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u19wi-b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:discord-solid" {...props}></Icon>
