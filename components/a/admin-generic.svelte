<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu3898bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tu3898bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-generic" {...props}></Icon>
