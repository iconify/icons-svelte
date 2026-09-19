<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe78kyb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pe78kyb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:hide-2" {...props}></Icon>
