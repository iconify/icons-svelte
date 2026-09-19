<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sax_p1s3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sax_p1s3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:prusa-mini" {...props}></Icon>
