<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr55tcb6u.css';
import '../../css/o/oh0uss8kv.css';
import '../../css/j/jzxyxbtne.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 qr55tcb6u"/><path class="clr-i-solid clr-i-solid-path-2 oh0uss8kv"/><path class="clr-i-solid clr-i-solid-path-3 jzxyxbtne"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:file-group-solid" {...props}></Icon>
