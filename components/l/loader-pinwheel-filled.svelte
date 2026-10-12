<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk2umei9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rk2umei9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:loader-pinwheel-filled" {...props}></Icon>
