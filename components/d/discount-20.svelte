<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmd-u84-k.css';
import '../../css/h/h9ysk2g4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gmd-u84-k"/><path class="h9ysk2g4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:discount-20" {...props}></Icon>
