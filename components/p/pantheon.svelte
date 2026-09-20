<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7xnroufn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7xnroufn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pantheon" {...props}></Icon>
