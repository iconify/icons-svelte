<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erl6f0bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="erl6f0bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pyramid-shape-remix" {...props}></Icon>
