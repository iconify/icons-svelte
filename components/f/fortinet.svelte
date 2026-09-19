<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skiqrcdfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skiqrcdfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:fortinet" {...props}></Icon>
