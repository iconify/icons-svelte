<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud5lazbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":819,"height":750};
const content = `<path class="ud5lazbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:hot" {...props}></Icon>
