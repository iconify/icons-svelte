<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn6g9f1_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn6g9f1_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mx-linux" {...props}></Icon>
