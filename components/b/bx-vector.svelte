<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uswlc2bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uswlc2bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-vector" {...props}></Icon>
