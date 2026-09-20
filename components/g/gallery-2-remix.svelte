<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1pqg6vdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="c1pqg6vdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:gallery-2-remix" {...props}></Icon>
