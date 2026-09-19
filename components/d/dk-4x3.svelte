<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb1o4ibht.css';
import '../../css/n/ngyu4emsk.css';
import '../../css/x/xin1hzb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="pb1o4ibht"/><path class="ngyu4emsk"/><path class="xin1hzb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:dk-4x3" {...props}></Icon>
