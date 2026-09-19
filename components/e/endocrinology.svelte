<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yql84dbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yql84dbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:endocrinology" {...props}></Icon>
