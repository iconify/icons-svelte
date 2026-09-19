<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnrj1sbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vnrj1sbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:number-stroke-12" {...props}></Icon>
