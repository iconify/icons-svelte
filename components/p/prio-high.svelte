<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak3isib6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ak3isib6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:prio-high" {...props}></Icon>
