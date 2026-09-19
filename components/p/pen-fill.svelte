<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wotq_yd3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wotq_yd3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:pen-fill" {...props}></Icon>
