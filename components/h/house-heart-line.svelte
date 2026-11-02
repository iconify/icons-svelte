<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-euov8ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-euov8ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:house-heart-line" {...props}></Icon>
