<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agdi52bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="agdi52bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:clock-plus-fill" {...props}></Icon>
