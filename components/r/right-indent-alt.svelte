<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih0nrxghi.css';
import '../../css/v/ve2abo9wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih0nrxghi"/><path class="ve2abo9wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:right-indent-alt" {...props}></Icon>
