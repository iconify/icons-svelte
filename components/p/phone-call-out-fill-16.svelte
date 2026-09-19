<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4m4ghapt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g4m4ghapt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-out-fill-16" {...props}></Icon>
