<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keu3it29w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="keu3it29w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-being" {...props}></Icon>
