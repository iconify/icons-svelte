<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpgw6lgbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpgw6lgbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:midi-line" {...props}></Icon>
