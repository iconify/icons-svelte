<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb6-0kbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lb6-0kbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:door-remix" {...props}></Icon>
