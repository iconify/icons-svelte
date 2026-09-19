<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzf93bbes.css';
import '../../css/f/fy34vxb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzf93bbes"/><path clip-rule="evenodd" class="fy34vxb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:copy-outline" {...props}></Icon>
