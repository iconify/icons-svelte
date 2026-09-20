<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9ngsnuyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9ngsnuyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-right-sharp-two-tone" {...props}></Icon>
