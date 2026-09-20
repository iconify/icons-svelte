<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gajxa_bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gajxa_bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:compress-pdf-solid" {...props}></Icon>
