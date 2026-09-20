<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyvjf-bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gyvjf-bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:attachment-outline" {...props}></Icon>
