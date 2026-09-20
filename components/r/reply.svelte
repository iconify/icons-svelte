<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et1pwobxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="et1pwobxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:reply" {...props}></Icon>
