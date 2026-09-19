<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaxi56bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gaxi56bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlepencil" {...props}></Icon>
