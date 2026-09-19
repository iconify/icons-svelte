<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m82vr8baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m82vr8baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pandatag" {...props}></Icon>
