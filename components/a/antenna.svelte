<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etcv1ib3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":897,"height":1024};
const content = `<path class="etcv1ib3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:antenna" {...props}></Icon>
