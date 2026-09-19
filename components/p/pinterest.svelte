<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2l6otbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x2l6otbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:pinterest" {...props}></Icon>
