<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fncit8v1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fncit8v1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:fuel-filled" {...props}></Icon>
