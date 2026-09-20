<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu1xf2bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gu1xf2bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:magnet-solid" {...props}></Icon>
