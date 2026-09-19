<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7gabzios.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="p7gabzios"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-left-circle" {...props}></Icon>
