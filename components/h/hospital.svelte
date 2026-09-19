<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7jvan2yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7jvan2yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:hospital" {...props}></Icon>
