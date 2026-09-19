<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy3ilwg6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy3ilwg6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:cync" {...props}></Icon>
