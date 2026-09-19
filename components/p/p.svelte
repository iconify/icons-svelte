<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prou6k_-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="prou6k_-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:p" {...props}></Icon>
