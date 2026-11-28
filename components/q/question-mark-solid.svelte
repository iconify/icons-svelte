<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr42u6bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr42u6bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:question-mark-solid" {...props}></Icon>
