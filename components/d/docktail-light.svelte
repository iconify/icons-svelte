<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex6wzyber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ex6wzyber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docktail-light" {...props}></Icon>
