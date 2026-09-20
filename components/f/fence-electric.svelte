<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to364ober.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to364ober"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fence-electric" {...props}></Icon>
