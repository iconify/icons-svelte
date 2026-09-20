<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve3a99k9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve3a99k9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fresh" {...props}></Icon>
