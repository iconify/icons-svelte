<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad4la_mph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad4la_mph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:rocket" {...props}></Icon>
