<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyafseb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyafseb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-k" {...props}></Icon>
