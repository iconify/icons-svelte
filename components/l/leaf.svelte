<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reyt_ebqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="reyt_ebqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:leaf" {...props}></Icon>
