<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpru91b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpru91b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:hamburger" {...props}></Icon>
