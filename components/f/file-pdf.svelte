<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q49xl5b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q49xl5b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:file-pdf" {...props}></Icon>
