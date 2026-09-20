<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd6l4xbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hd6l4xbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:inbox-post-remix" {...props}></Icon>
