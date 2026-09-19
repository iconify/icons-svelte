<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udd-1hb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udd-1hb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:emergency-health-filled" {...props}></Icon>
