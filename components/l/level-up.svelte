<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt4lrqb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qt4lrqb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:level-up" {...props}></Icon>
