<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaw-bkn7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uaw-bkn7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:colon" {...props}></Icon>
