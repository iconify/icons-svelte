<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frjvp-1mk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="frjvp-1mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:box-solid" {...props}></Icon>
