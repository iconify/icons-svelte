<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8ke5gh1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h8ke5gh1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:open-in-new-tab" {...props}></Icon>
