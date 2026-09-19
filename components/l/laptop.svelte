<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3d185x6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3d185x6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:laptop" {...props}></Icon>
