<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psonnacff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psonnacff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:expo" {...props}></Icon>
