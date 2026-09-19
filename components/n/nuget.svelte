<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkblh9o1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lkblh9o1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:nuget" {...props}></Icon>
