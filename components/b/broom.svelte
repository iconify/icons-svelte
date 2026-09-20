<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpz4-dbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rpz4-dbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:broom" {...props}></Icon>
