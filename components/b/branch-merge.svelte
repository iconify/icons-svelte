<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grrt2gedn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="grrt2gedn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:branch-merge" {...props}></Icon>
