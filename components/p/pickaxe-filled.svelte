<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6vl68bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y6vl68bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pickaxe-filled" {...props}></Icon>
