<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqtki0bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="fqtki0bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:gift" {...props}></Icon>
