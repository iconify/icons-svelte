<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_vq-abkk.css';
import '../../css/i/i83sn7bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i_vq-abkk"/><path class="i83sn7bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:high-priority" {...props}></Icon>
