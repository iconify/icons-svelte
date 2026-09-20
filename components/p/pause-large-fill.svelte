<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oteru_gyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oteru_gyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pause-large-fill" {...props}></Icon>
