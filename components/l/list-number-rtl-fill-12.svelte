<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdh42-b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rdh42-b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:list-number-rtl-fill-12" {...props}></Icon>
