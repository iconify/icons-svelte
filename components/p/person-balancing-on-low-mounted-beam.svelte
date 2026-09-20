<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2o5zgssc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t2o5zgssc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-balancing-on-low-mounted-beam" {...props}></Icon>
