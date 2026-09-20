<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwntovrda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwntovrda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pilcrow-solid" {...props}></Icon>
