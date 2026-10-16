<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u95e4sw8e.css';
import '../../css/l/lfn44k03n.css';
import '../../css/i/i_mq2ccik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u95e4sw8e"/><path class="lfn44k03n"/><path class="i_mq2ccik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-plus-48-bold" {...props}></Icon>
