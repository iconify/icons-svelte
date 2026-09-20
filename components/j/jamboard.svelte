<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj4baj38d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj4baj38d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jamboard" {...props}></Icon>
