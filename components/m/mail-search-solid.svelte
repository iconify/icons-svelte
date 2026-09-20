<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay24x4blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ay24x4blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-search-solid" {...props}></Icon>
