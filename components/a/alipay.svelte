<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avd1rxbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="avd1rxbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:alipay" {...props}></Icon>
