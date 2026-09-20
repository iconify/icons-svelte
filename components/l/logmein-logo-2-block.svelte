<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrbyutbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rrbyutbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:logmein-logo-2-block" {...props}></Icon>
