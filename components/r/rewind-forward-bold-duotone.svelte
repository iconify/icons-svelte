<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctu7he3ei.css';
import '../../css/m/mrqs5-_hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ctu7he3ei"/><path class="mrqs5-_hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-forward-bold-duotone" {...props}></Icon>
