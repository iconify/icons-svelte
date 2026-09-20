<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td4f8bzwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td4f8bzwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:highlighter" {...props}></Icon>
