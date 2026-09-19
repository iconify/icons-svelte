<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnebau0iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="hnebau0iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:receipt" {...props}></Icon>
