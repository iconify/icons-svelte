<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k46bqabvm.css';
import '../../css/i/iqzoboglm.css';
import '../../css/t/tvdh9jgjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k46bqabvm"/><path class="iqzoboglm"/><path class="tvdh9jgjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-manager" {...props}></Icon>
