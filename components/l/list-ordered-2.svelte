<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn2gqpb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn2gqpb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:list-ordered-2" {...props}></Icon>
