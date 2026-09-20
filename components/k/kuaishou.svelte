<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhzv1zwvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhzv1zwvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kuaishou" {...props}></Icon>
