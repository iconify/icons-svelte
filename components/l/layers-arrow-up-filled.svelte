<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8i9flbaf.css';
import '../../css/n/njfu2s7nv.css';
import '../../css/y/yhgcxzo7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8i9flbaf"/><path class="njfu2s7nv"/><path class="yhgcxzo7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layers-arrow-up-filled" {...props}></Icon>
