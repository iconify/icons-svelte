<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg4prrbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg4prrbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-item-right-fill" {...props}></Icon>
