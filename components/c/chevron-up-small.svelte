<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4om_whwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4om_whwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:chevron-up-small" {...props}></Icon>
