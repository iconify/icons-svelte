<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1bibsy4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1bibsy4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bleach-no-chlorine" {...props}></Icon>
