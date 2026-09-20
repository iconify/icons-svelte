<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9a7r7b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x9a7r7b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:quotation-2-solid" {...props}></Icon>
