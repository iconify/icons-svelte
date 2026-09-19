<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2k8g2b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="y2k8g2b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:master-database" {...props}></Icon>
