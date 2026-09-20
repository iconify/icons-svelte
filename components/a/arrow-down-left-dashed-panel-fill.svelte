<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek5tstf8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek5tstf8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-left-dashed-panel-fill" {...props}></Icon>
