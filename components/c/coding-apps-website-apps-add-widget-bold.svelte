<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daap6e5ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="daap6e5ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coding-apps-website-apps-add-widget-bold" {...props}></Icon>
