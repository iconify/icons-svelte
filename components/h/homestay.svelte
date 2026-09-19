<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg2il3bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qg2il3bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:homestay" {...props}></Icon>
