<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtqd48bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtqd48bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:indigo" {...props}></Icon>
