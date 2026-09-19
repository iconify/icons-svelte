<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2axmbbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2axmbbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-fugato-two-alt" {...props}></Icon>
