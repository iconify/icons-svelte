<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtyb8y3nc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtyb8y3nc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hey" {...props}></Icon>
