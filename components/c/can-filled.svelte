<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt_o1d_3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lt_o1d_3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:can-filled" {...props}></Icon>
