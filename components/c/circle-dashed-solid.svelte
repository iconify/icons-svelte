<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzt5u7bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzt5u7bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:circle-dashed-solid" {...props}></Icon>
