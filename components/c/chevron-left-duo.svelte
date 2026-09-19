<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpi2c7bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpi2c7bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-left-duo" {...props}></Icon>
