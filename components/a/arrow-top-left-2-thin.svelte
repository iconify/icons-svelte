<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu4uyrb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu4uyrb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-2-thin" {...props}></Icon>
