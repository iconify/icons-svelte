<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nivk-30wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nivk-30wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cc" {...props}></Icon>
