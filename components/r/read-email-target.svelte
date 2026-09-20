<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew0ia5buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ew0ia5buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:read-email-target" {...props}></Icon>
