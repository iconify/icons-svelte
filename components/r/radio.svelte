<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcagx4xdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hcagx4xdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:radio" {...props}></Icon>
