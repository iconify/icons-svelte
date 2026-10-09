<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su5nz9bnp.css';
import '../../css/c/c-q5u1bet.css';
import '../../css/w/w6bhw7baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="su5nz9bnp"/><path class="c-q5u1bet"/><path class="w6bhw7baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:green-hydrogen-48" {...props}></Icon>
