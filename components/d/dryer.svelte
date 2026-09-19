<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doo-tobgu.css';
import '../../css/a/atcuyybgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doo-tobgu"/><path class="atcuyybgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:dryer" {...props}></Icon>
