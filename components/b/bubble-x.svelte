<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt9bn2uhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt9bn2uhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bubble-x" {...props}></Icon>
