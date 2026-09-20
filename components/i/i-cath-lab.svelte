<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwigj8bqa.css';
import '../../css/f/fvz0x3bpb.css';
import '../../css/z/zg0gl4b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="dwigj8bqa"/><path class="fvz0x3bpb"/><path class="zg0gl4b4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-cath-lab" {...props}></Icon>
