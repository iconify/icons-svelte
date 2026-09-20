<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg93ylblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gg93ylblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:cog-automation-remix" {...props}></Icon>
