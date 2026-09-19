<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzfce9bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49,"height":48};
const content = `<path class="xzfce9bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:kettle" {...props}></Icon>
