<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t90_9xbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t90_9xbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:92x-outline" {...props}></Icon>
