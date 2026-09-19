<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhhac4b9m.css';
import '../../css/a/a2-rokb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qhhac4b9m"/><path class="a2-rokb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:arc" {...props}></Icon>
