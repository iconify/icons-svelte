<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmkxlo5-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmkxlo5-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:polaroid-solid" {...props}></Icon>
