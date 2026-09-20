<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjnv7wj5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjnv7wj5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:eye-closed" {...props}></Icon>
