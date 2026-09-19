<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua11ue-al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ua11ue-al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:emissions" {...props}></Icon>
