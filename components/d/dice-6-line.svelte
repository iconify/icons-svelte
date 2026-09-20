<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uopdy0hhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uopdy0hhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dice-6-line" {...props}></Icon>
