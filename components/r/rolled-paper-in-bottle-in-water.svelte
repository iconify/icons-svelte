<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwq-kcccm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jwq-kcccm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rolled-paper-in-bottle-in-water" {...props}></Icon>
