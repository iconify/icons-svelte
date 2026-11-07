<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv14xiw-u.css';
import '../../css/z/zol642wmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv14xiw-u"/><path clip-rule="evenodd" class="zol642wmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-right-bold-duotone" {...props}></Icon>
