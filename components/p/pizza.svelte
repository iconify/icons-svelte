<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2_fttfir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2_fttfir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:pizza" {...props}></Icon>
