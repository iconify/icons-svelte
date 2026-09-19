<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgata2vhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kgata2vhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:grid-sharp" {...props}></Icon>
