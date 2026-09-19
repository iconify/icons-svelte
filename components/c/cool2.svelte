<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yif4bibhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yif4bibhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:cool2" {...props}></Icon>
