<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw83z9b-r.css';
import '../../css/t/t9-82h_yw.css';
import '../../css/j/j0c-zxbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k zw83z9b-r"/><path class="t9-82h_yw wm-k"/><path class="j0c-zxbrk wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:indent-decrease" {...props}></Icon>
