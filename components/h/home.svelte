<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dshlk0khp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="dshlk0khp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:home" {...props}></Icon>
