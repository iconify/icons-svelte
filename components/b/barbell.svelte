<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hko1tx88j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hko1tx88j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:barbell" {...props}></Icon>
