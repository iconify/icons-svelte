<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy9jdhnbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wy9jdhnbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cupcake-filled" {...props}></Icon>
