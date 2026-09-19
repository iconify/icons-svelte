<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io23o0drw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io23o0drw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:contact" {...props}></Icon>
