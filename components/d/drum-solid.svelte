<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av5mm9bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av5mm9bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:drum-solid" {...props}></Icon>
