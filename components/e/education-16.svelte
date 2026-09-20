<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf7r-wbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zf7r-wbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:education-16" {...props}></Icon>
