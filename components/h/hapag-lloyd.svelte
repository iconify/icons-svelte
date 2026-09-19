<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc11kh5kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc11kh5kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hapag-lloyd" {...props}></Icon>
