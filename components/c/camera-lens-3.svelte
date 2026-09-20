<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giv3sgb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="giv3sgb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:camera-lens-3" {...props}></Icon>
