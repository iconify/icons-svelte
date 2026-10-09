<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry85_ib5t.css';
import '../../css/g/g7joh4_lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ry85_ib5t"/><path class="g7joh4_lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flag-48" {...props}></Icon>
