<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqakt6x8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jqakt6x8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:beach-remix" {...props}></Icon>
