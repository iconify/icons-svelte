<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm24f5buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jm24f5buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bank-20" {...props}></Icon>
