<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2xjy9bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2xjy9bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:brush-alt" {...props}></Icon>
