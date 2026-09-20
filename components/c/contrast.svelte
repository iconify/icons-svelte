<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teyd1mnlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="teyd1mnlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:contrast" {...props}></Icon>
