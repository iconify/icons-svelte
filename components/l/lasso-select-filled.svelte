<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoqiw4b5c.css';
import '../../css/l/lg9rrm_lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoqiw4b5c"/><path class="lg9rrm_lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lasso-select-filled" {...props}></Icon>
