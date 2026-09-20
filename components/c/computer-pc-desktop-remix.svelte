<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn6bwj6xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gn6bwj6xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:computer-pc-desktop-remix" {...props}></Icon>
