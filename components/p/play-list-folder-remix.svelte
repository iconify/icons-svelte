<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd6hbhzah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vd6hbhzah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:play-list-folder-remix" {...props}></Icon>
