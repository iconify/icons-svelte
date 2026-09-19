<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nprmtcb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nprmtcb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:friends-of-hue-aurora-dimmer-switch-alt" {...props}></Icon>
