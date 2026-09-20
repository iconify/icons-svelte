<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2npvv7bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v2npvv7bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-align-center" {...props}></Icon>
