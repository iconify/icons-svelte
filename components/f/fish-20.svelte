<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3m6qu31q.css';
import '../../css/q/qe6mnv44d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b3m6qu31q"/><path class="qe6mnv44d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fish-20" {...props}></Icon>
