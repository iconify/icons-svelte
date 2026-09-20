<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa309cbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa309cbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googlemybusiness" {...props}></Icon>
