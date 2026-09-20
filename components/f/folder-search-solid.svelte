<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klk01p-xy.css';
import '../../css/l/lsqc0acbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klk01p-xy"/><path clip-rule="evenodd" class="lsqc0acbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-search-solid" {...props}></Icon>
