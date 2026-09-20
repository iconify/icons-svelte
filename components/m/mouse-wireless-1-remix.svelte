<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbqu5pbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gbqu5pbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mouse-wireless-1-remix" {...props}></Icon>
