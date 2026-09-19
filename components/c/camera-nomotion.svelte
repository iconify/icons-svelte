<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zipr6oyhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zipr6oyhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:camera-nomotion" {...props}></Icon>
