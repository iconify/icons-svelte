<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3tor9bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3tor9bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dreamcast" {...props}></Icon>
