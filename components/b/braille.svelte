<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5-8qbbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2176,"height":1408};
const content = `<path class="q5-8qbbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:braille" {...props}></Icon>
