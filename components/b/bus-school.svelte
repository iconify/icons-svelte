<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfth7oboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfth7oboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bus-school" {...props}></Icon>
