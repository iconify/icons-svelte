<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuhzw_-te.css';
import '../../css/g/gn7buhpvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":9,"height":16};
const content = `<path class="zuhzw_-te"/><path class="gn7buhpvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:arrowdown" {...props}></Icon>
