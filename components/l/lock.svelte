<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymekm1b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymekm1b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:lock" {...props}></Icon>
