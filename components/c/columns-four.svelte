<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whf6808kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whf6808kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:columns-four" {...props}></Icon>
