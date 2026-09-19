<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctcl7tbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctcl7tbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:menu-duo-lg" {...props}></Icon>
