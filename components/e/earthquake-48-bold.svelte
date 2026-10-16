<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjw2pb06u.css';
import '../../css/e/e55pc6bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mjw2pb06u"/><path class="e55pc6bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:earthquake-48-bold" {...props}></Icon>
