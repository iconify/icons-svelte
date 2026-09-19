<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvi9l7iyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gvi9l7iyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cloud-circle" {...props}></Icon>
