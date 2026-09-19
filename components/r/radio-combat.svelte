<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp9a7dbdx.css';
import '../../css/d/dcr78hbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gp9a7dbdx"/><path class="dcr78hbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:radio-combat" {...props}></Icon>
