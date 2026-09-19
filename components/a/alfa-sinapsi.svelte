<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aylfalb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aylfalb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:alfa-sinapsi" {...props}></Icon>
