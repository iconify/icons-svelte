<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r66vghbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r66vghbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-through-line-solid" {...props}></Icon>
