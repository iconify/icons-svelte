<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwox1tbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cwox1tbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:not-available" {...props}></Icon>
