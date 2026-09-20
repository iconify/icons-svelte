<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrew4e9yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vrew4e9yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:play-list-folder-solid" {...props}></Icon>
