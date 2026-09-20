<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp4ro4bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xp4ro4bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:oval-broadleaved-tree" {...props}></Icon>
