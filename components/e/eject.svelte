<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_r4um0nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_r4um0nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:eject" {...props}></Icon>
