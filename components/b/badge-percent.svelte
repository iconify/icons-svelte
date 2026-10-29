<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsvhz9bpc.css';
import '../../css/u/ui3j74sqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsvhz9bpc wm-k"/><path class="ui3j74sqk wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:badge-percent" {...props}></Icon>
