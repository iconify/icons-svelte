<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grgrw979e.css';
import '../../css/w/wu8h8ib5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="grgrw979e"/><path class="wu8h8ib5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-right-48-bold" {...props}></Icon>
