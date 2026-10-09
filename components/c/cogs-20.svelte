<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc234ccnu.css';
import '../../css/v/v0_7k5btb.css';
import '../../css/r/rbyjwpwup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kc234ccnu"/><path class="v0_7k5btb"/><path class="rbyjwpwup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cogs-20" {...props}></Icon>
