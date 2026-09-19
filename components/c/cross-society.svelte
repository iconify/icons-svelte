<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knsfwrm4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="knsfwrm4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:cross-society" {...props}></Icon>
