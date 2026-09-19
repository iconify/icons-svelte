<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqbw-sb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqbw-sb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:music-solid" {...props}></Icon>
