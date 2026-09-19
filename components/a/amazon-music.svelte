<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppja7jg2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppja7jg2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:amazon-music" {...props}></Icon>
