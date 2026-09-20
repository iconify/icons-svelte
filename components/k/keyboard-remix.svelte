<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib3aw7l4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ib3aw7l4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:keyboard-remix" {...props}></Icon>
