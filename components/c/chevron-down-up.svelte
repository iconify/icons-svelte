<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q38v2vbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q38v2vbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-down-up" {...props}></Icon>
