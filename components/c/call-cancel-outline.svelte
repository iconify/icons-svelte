<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux5jk213g.css';
import '../../css/l/l8p24vbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ux5jk213g"/><path class="l8p24vbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-cancel-outline" {...props}></Icon>
