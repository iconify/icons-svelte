<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikn_s50ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikn_s50ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heading-6-fill-round" {...props}></Icon>
