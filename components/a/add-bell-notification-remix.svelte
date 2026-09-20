<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz84blb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kz84blb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:add-bell-notification-remix" {...props}></Icon>
