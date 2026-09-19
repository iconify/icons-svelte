<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbs-olz4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tbs-olz4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:back" {...props}></Icon>
