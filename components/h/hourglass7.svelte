<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo8ctyb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bo8ctyb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:hourglass7" {...props}></Icon>
