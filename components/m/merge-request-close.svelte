<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz2fpklzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jz2fpklzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:merge-request-close" {...props}></Icon>
