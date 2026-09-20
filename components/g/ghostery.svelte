<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f574bg4zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f574bg4zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ghostery" {...props}></Icon>
