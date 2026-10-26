<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnai2pbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnai2pbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:komodo" {...props}></Icon>
