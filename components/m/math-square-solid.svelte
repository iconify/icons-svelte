<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htgra2j3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htgra2j3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:math-square-solid" {...props}></Icon>
