<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu5e9je0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wu5e9je0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-outgoing-remix" {...props}></Icon>
