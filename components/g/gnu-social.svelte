<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1vq49b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1vq49b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gnu-social" {...props}></Icon>
