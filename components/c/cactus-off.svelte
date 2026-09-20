<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnj__0ttb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnj__0ttb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cactus-off" {...props}></Icon>
