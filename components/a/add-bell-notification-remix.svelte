<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_h731ysk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p_h731ysk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:add-bell-notification-remix" {...props}></Icon>
