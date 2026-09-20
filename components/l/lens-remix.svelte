<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvhjbhcuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rvhjbhcuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:lens-remix" {...props}></Icon>
