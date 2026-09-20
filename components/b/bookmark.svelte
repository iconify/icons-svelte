<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h36y6dxnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h36y6dxnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:bookmark" {...props}></Icon>
