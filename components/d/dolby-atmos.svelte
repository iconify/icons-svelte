<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp99ldnqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp99ldnqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dolby-atmos" {...props}></Icon>
