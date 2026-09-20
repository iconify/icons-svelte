<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbp-vjqrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbp-vjqrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-focus" {...props}></Icon>
