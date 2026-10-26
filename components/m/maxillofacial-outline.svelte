<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv4ofb8wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xv4ofb8wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:maxillofacial-outline" {...props}></Icon>
