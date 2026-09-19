<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoyi67mez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoyi67mez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-top-left" {...props}></Icon>
