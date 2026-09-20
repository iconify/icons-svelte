<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qggk3jboh.css';
import '../../css/t/tkr_52btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qggk3jboh"/><path class="tkr_52btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:laptop-computer-smiley" {...props}></Icon>
