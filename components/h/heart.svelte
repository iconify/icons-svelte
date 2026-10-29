<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b38sfdbfi.css';
import '../../css/y/yoahqrgnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b38sfdbfi"/><path class="yoahqrgnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:heart" {...props}></Icon>
