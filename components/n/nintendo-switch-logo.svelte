<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osn55wydk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osn55wydk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nintendo-switch-logo" {...props}></Icon>
