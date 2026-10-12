<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3uhkpz7r.css';
import '../../css/j/j_u0kbnup.css';
import '../../css/v/v-u3t3bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f3uhkpz7r"/><path class="j_u0kbnup"/><path class="v-u3t3bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plumb-bob-20-bold" {...props}></Icon>
