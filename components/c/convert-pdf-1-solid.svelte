<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp10abbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bp10abbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:convert-pdf-1-solid" {...props}></Icon>
