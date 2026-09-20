<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi796lndd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mi796lndd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gas" {...props}></Icon>
