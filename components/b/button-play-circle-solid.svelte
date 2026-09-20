<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1q4mqbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i1q4mqbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:button-play-circle-solid" {...props}></Icon>
