<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb-2c0eis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gb-2c0eis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:picnic-table" {...props}></Icon>
