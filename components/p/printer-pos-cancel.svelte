<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctsraib4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctsraib4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-pos-cancel" {...props}></Icon>
