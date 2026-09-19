<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soz8xib7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="soz8xib7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:home" {...props}></Icon>
