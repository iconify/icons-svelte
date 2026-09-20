<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj1-1-_to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj1-1-_to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lamborghini" {...props}></Icon>
