<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzsv4fboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzsv4fboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:equalizer-fill" {...props}></Icon>
