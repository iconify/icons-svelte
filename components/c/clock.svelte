<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htc4simvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="htc4simvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:clock" {...props}></Icon>
