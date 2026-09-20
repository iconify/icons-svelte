<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qboix9yzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qboix9yzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:chip" {...props}></Icon>
