<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxhk30f5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zxhk30f5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:bulb" {...props}></Icon>
