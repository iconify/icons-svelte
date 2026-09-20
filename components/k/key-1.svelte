<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz5clsphv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uz5clsphv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:key-1" {...props}></Icon>
