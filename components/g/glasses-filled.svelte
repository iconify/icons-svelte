<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbw2wbk-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbw2wbk-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:glasses-filled" {...props}></Icon>
