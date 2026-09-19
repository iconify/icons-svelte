<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqzf6mblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wqzf6mblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cpap-tubes-outline" {...props}></Icon>
