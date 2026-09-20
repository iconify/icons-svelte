<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppbprwb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppbprwb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-more-horizontal-fill" {...props}></Icon>
