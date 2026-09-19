<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kis9mmb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kis9mmb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:auto-fit-contents" {...props}></Icon>
