<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/posqd9bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="posqd9bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:activision" {...props}></Icon>
