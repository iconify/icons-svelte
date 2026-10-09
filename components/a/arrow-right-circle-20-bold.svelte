<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0oa-qzdz.css';
import '../../css/u/u1--n3bbd.css';
import '../../css/w/wwqa-8bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="u1--n3bbd"/><path class="wwqa-8bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-right-circle-20-bold" {...props}></Icon>
