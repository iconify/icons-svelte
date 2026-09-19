<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c33a4rbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c33a4rbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:left-down-arrow-circle" {...props}></Icon>
