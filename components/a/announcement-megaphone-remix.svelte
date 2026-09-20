<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0a033v1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n0a033v1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:announcement-megaphone-remix" {...props}></Icon>
