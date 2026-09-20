<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awwm6x5ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awwm6x5ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:lock-off-filled" {...props}></Icon>
