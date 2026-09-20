<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig55-lw-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig55-lw-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mobile-signal-four-solid" {...props}></Icon>
