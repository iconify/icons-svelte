<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_my_xc0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a_my_xc0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:journal-sharp" {...props}></Icon>
