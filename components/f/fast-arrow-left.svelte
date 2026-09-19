<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m05_qabul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m05_qabul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fast-arrow-left" {...props}></Icon>
