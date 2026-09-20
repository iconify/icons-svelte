<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0zucx8cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x0zucx8cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:education" {...props}></Icon>
