<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgxa5ewbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgxa5ewbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:github" {...props}></Icon>
