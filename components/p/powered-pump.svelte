<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lez76uq7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lez76uq7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:powered-pump" {...props}></Icon>
