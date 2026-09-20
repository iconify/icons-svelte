<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvkf72bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvkf72bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:github" {...props}></Icon>
