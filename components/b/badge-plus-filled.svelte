<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzo4to9sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fzo4to9sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-plus-filled" {...props}></Icon>
