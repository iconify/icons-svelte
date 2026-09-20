<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvr_ly5gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hvr_ly5gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:elbow-connector-solid" {...props}></Icon>
