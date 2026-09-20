<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epx26fbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epx26fbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:align" {...props}></Icon>
