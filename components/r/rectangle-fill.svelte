<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lya76wdsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lya76wdsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-fill" {...props}></Icon>
