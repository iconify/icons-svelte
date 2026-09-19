<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb6wl9bmp.css';
import '../../css/b/b56j2525l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kb6wl9bmp"/><path class="b56j2525l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chevron-circle-right-alt" {...props}></Icon>
