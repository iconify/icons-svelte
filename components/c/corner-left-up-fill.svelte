<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnufhebgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnufhebgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-left-up-fill" {...props}></Icon>
