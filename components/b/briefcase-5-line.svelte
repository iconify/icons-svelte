<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsebfx-jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsebfx-jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:briefcase-5-line" {...props}></Icon>
