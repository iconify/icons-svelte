<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzf2h5bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzf2h5bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:desktop-computer" {...props}></Icon>
