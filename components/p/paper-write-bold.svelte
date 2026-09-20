<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw5u4miyi.css';
import '../../css/b/b2dxt0bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw5u4miyi"/><path class="b2dxt0bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:paper-write-bold" {...props}></Icon>
