<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mob82fcgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mob82fcgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:redhat" {...props}></Icon>
