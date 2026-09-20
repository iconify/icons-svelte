<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnah_ob2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rnah_ob2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:programming-bug" {...props}></Icon>
