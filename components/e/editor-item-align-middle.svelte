<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smkpeh00y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="smkpeh00y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-item-align-middle" {...props}></Icon>
