<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqw4e6bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqw4e6bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:craftsman" {...props}></Icon>
