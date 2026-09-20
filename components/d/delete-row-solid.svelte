<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blt9aqlsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="blt9aqlsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:delete-row-solid" {...props}></Icon>
