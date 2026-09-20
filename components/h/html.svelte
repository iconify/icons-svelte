<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loy38wo6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="loy38wo6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:html" {...props}></Icon>
