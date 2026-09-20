<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrbbr2bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zrbbr2bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:color-picker-solid" {...props}></Icon>
