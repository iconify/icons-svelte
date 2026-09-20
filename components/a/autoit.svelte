<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kon4bwbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kon4bwbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:autoit" {...props}></Icon>
