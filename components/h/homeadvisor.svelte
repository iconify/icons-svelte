<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkxhi7n1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkxhi7n1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:homeadvisor" {...props}></Icon>
