<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2wsqgbwj.css';
import '../../css/j/jzphsob0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f2wsqgbwj"/><path class="jzphsob0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kick-scooter-20" {...props}></Icon>
