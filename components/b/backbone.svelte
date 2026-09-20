<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph7pkv8aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ph7pkv8aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:backbone" {...props}></Icon>
