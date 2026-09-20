<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqmlo2b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lqmlo2b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:chart" {...props}></Icon>
