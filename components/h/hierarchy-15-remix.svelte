<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg7s50srv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rg7s50srv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:hierarchy-15-remix" {...props}></Icon>
