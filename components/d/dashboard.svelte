<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q66mwfb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="q66mwfb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:dashboard" {...props}></Icon>
