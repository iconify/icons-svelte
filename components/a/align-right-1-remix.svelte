<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjso1ccoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bjso1ccoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:align-right-1-remix" {...props}></Icon>
