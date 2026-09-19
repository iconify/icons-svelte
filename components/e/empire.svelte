<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czd8gk1ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="czd8gk1ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:empire" {...props}></Icon>
