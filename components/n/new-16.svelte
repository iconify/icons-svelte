<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kic12wbzz.css';
import '../../css/h/hm17yp49j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kic12wbzz"/><path clip-rule="evenodd" class="hm17yp49j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:new-16" {...props}></Icon>
