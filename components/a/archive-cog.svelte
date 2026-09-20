<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffok7h96d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffok7h96d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-cog" {...props}></Icon>
