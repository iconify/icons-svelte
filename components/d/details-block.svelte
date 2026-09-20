<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw3hutb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zw3hutb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:details-block" {...props}></Icon>
