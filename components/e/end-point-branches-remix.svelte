<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5ymsbbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j5ymsbbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:end-point-branches-remix" {...props}></Icon>
