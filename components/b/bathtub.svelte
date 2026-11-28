<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at12u8goe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at12u8goe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bathtub" {...props}></Icon>
