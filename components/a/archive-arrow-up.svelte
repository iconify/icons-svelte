<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf0x6_f6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf0x6_f6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:archive-arrow-up" {...props}></Icon>
