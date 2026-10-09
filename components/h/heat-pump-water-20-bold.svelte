<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs_q2h7oe.css';
import '../../css/p/pk1wthwad.css';
import '../../css/b/broi4tbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xs_q2h7oe"/><path class="pk1wthwad"/><path class="broi4tbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-water-20-bold" {...props}></Icon>
