<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za4ik9b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za4ik9b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:hashtag" {...props}></Icon>
