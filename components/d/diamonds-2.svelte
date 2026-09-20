<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inel58btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inel58btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:diamonds-2" {...props}></Icon>
