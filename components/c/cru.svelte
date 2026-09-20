<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7tplmbgr.css';
import '../../css/j/jj8ei-gdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7tplmbgr"/><path class="jj8ei-gdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cru" {...props}></Icon>
