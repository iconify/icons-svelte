<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huf-eeblg.css';
import '../../css/a/arr-9f6dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="huf-eeblg"/><path class="arr-9f6dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:minus-circle" {...props}></Icon>
