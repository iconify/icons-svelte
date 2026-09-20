<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs058csvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs058csvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:facebooklive" {...props}></Icon>
