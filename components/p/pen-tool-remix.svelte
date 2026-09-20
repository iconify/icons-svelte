<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po87b7bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="po87b7bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pen-tool-remix" {...props}></Icon>
