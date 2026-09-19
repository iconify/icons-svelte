<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsohd1-ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsohd1-ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:coin" {...props}></Icon>
