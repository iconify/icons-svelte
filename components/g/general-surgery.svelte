<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6qh3ib3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v6qh3ib3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:general-surgery" {...props}></Icon>
