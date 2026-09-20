<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji5q-_b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ji5q-_b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:home-1" {...props}></Icon>
