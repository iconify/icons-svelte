<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tumc10bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tumc10bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:new-folder-remix" {...props}></Icon>
