<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-ali6xtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i-ali6xtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-search-remix" {...props}></Icon>
