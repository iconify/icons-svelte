<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqyt8qbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kqyt8qbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pound-outline" {...props}></Icon>
