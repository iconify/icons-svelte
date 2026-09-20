<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3931nyet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3931nyet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-drop-left-fill" {...props}></Icon>
