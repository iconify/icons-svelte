<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzwts81us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":1024};
const content = `<path class="tzwts81us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mongodb" {...props}></Icon>
