<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4tooib-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="m4tooib-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:instagram" {...props}></Icon>
