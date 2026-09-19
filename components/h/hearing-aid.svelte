<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bikzi3bkv.css';
import '../../css/l/l-d0mzbnh.css';
import '../../css/v/v45s4tbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bikzi3bkv"/><path class="l-d0mzbnh"/><path class="v45s4tbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:hearing-aid" {...props}></Icon>
