<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayv_5ub6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ayv_5ub6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-pencil-fill" {...props}></Icon>
