<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjfst8bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjfst8bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:phone-3" {...props}></Icon>
