<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy1kzqb5s.css';
import '../../css/b/bgsh7qxku.css';
import '../../css/k/k4oa-tklo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oy1kzqb5s"/><path class="bgsh7qxku"/><path class="k4oa-tklo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:entering-heaven-alive" {...props}></Icon>
