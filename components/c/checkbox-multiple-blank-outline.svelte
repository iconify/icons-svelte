<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e710hqb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e710hqb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkbox-multiple-blank-outline" {...props}></Icon>
