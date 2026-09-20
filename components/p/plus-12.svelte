<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k96tsedlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="k96tsedlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:plus-12" {...props}></Icon>
