<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1u8bfmde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="i1u8bfmde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:message-user" {...props}></Icon>
