<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nruagvb1s.css';
import '../../css/t/tc8s89bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nruagvb1s"/><path class="tc8s89bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-animation" {...props}></Icon>
