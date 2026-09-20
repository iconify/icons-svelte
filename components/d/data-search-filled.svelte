<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1-dclb0l.css';
import '../../css/n/nuuqustnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="t1-dclb0l"/><path class="nuuqustnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:data-search-filled" {...props}></Icon>
