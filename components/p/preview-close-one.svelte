<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tar6cn05y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tar6cn05y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:preview-close-one" {...props}></Icon>
