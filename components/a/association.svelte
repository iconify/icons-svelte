<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz5v46qeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zz5v46qeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:association" {...props}></Icon>
