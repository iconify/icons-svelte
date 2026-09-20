<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njstg7eby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njstg7eby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:magic" {...props}></Icon>
