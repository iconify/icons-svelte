<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyz64c2_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lyz64c2_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:arrow-expand-flat" {...props}></Icon>
