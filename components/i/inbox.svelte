<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eho36mb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eho36mb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:inbox" {...props}></Icon>
