<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f178wil9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f178wil9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-from-line" {...props}></Icon>
