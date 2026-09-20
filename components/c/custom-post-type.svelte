<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eagz4xafi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="eagz4xafi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:custom-post-type" {...props}></Icon>
