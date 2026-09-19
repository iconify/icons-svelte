<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5q2e8byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t5q2e8byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:papyrus" {...props}></Icon>
