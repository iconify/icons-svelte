<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5om8e96x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5om8e96x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:code-not-equal-variant" {...props}></Icon>
