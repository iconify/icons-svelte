<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snn4fxhfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snn4fxhfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:imdb-logo" {...props}></Icon>
