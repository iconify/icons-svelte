<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqt8gccuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqt8gccuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bell-off-solid" {...props}></Icon>
