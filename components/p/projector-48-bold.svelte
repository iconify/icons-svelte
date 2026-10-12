<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab8fc_wvr.css';
import '../../css/z/zd05-xlem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ab8fc_wvr"/><path class="zd05-xlem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:projector-48-bold" {...props}></Icon>
