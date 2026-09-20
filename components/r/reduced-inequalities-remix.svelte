<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3rkaj_9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q3rkaj_9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:reduced-inequalities-remix" {...props}></Icon>
