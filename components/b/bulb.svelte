<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq1jzcbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="lq1jzcbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bulb" {...props}></Icon>
