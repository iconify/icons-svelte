<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j37p8-b4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j37p8-b4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:moustache-remix" {...props}></Icon>
