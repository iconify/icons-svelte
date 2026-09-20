<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk6fdg-6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="wk6fdg-6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:line-solid" {...props}></Icon>
