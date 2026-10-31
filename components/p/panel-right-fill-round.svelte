<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y20p6kbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y20p6kbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-right-fill-round" {...props}></Icon>
