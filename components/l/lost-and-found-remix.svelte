<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro9w7mcms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ro9w7mcms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:lost-and-found-remix" {...props}></Icon>
