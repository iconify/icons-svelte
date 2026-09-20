<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibiavqbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibiavqbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:play-box-multiple-outline" {...props}></Icon>
