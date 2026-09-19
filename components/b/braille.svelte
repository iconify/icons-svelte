<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc3hpb0xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc3hpb0xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:braille" {...props}></Icon>
