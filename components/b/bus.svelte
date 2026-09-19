<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp2apd1jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp2apd1jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:bus" {...props}></Icon>
