<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doo09ibxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="doo09ibxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pencil-square-remix" {...props}></Icon>
