<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjh95cbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zjh95cbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:insurance-hand" {...props}></Icon>
