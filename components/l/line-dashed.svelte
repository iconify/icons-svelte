<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaw9wkb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="zaw9wkb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:line-dashed" {...props}></Icon>
