<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0bszdh_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b0bszdh_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:hard-drive-2-remix" {...props}></Icon>
