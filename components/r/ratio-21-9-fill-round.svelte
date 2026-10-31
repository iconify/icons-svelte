<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq1ge0_ym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq1ge0_ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-21-9-fill-round" {...props}></Icon>
