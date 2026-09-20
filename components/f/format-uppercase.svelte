<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp_3u9b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="wp_3u9b4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:format-uppercase" {...props}></Icon>
