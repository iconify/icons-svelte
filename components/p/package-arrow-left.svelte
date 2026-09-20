<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv8-pwlcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv8-pwlcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package-arrow-left" {...props}></Icon>
