<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2lg9fbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2lg9fbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:avocado" {...props}></Icon>
