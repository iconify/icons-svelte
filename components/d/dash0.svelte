<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyjzgacii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyjzgacii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dash0" {...props}></Icon>
