<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu_r7z49s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hu_r7z49s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:rotate-left-1-remix" {...props}></Icon>
