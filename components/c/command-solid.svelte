<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5t95sj6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5t95sj6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:command-solid" {...props}></Icon>
