<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avn7-_bug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avn7-_bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:radio-off" {...props}></Icon>
