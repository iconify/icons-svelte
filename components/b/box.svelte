<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-0kz27_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="b-0kz27_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:box" {...props}></Icon>
