<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgsf-tbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgsf-tbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-top-bottom-dashed-filled" {...props}></Icon>
