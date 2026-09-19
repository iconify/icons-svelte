<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnxmi3-ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="mnxmi3-ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:equal-circle" {...props}></Icon>
