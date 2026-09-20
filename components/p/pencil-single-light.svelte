<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8f7hrbpl.css';
import '../../css/u/u9i0xe_nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8f7hrbpl"/><path clip-rule="evenodd" class="u9i0xe_nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pencil-single-light" {...props}></Icon>
