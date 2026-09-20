<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n51x8rmhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n51x8rmhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:phone-find-line" {...props}></Icon>
