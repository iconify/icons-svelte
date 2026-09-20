<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk2hbr6ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zk2hbr6ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:embeddedc" {...props}></Icon>
