<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y27aw59rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y27aw59rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:arrow-rotate" {...props}></Icon>
