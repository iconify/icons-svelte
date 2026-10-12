<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0tzg361r.css';
import '../../css/u/ubprlmtat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0tzg361r"/><path class="ubprlmtat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:battery-charging-filled" {...props}></Icon>
