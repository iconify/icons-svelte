<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzph_hspk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzph_hspk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:flow-chart-hierachy" {...props}></Icon>
