<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rccc1p87j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rccc1p87j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fruit-cherries" {...props}></Icon>
