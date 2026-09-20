<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiy1g7h8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiy1g7h8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:qualcomm-logo" {...props}></Icon>
