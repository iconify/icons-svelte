<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2v60eklz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="s2v60eklz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-button-zigzag-both-direction-arrow-curvy-diagram-zigzag-vertical" {...props}></Icon>
