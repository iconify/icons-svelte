<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6d4icc2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x6d4icc2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:circle-large-outline" {...props}></Icon>
