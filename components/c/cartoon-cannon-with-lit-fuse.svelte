<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe47tqu_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oe47tqu_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cartoon-cannon-with-lit-fuse" {...props}></Icon>
