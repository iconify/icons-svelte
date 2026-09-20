<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5mn2mbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="j5mn2mbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:grid" {...props}></Icon>
