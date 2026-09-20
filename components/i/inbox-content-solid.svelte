<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc0t97b9h.css';
import '../../css/d/do2f6-r1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jc0t97b9h"/><path class="do2f6-r1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:inbox-content-solid" {...props}></Icon>
