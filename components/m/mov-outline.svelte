<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feojym73l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="feojym73l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mov-outline" {...props}></Icon>
