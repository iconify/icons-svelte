<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jukv0ub1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="jukv0ub1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:caution" {...props}></Icon>
