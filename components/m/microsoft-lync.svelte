<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc_or7r6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kc_or7r6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:microsoft-lync" {...props}></Icon>
