<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx8kvybnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fx8kvybnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:business-progress-bar-2-remix" {...props}></Icon>
