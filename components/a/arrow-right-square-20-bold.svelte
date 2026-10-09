<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fec4cjbkq.css';
import '../../css/u/u1--n3bbd.css';
import '../../css/w/wwqa-8bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fec4cjbkq"/><path class="u1--n3bbd"/><path class="wwqa-8bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-right-square-20-bold" {...props}></Icon>
