<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihhe6fw-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihhe6fw-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:clapper-board" {...props}></Icon>
