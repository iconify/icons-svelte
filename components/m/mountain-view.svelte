<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l03ivrben.css';
import '../../css/w/wlmt3rjgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l03ivrben"/><path class="wlmt3rjgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mountain-view" {...props}></Icon>
