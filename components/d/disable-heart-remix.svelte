<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbew85u1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cbew85u1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:disable-heart-remix" {...props}></Icon>
