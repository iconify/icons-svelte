<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e24bgbccy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e24bgbccy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:paintbrush-fill" {...props}></Icon>
