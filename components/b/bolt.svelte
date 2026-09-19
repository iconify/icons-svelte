<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf8-odb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf8-odb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:bolt" {...props}></Icon>
