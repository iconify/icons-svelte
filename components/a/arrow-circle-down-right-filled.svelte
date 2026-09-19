<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7m7zsltm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7m7zsltm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-circle-down-right-filled" {...props}></Icon>
