<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj0jfeobs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lj0jfeobs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:8k" {...props}></Icon>
