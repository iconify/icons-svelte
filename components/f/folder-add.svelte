<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a696i2_mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a696i2_mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:folder-add" {...props}></Icon>
