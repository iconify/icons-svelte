<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw3driq-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bw3driq-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:description-remix" {...props}></Icon>
