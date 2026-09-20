<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cckl8wolt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cckl8wolt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:pill" {...props}></Icon>
