<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la_6nmkfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="la_6nmkfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lab-search2x-outline" {...props}></Icon>
