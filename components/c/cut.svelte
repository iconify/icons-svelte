<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trc-w2bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="trc-w2bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:cut" {...props}></Icon>
