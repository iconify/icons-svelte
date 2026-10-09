<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k98tn-izd.css';
import '../../css/m/mjb6-8gcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k98tn-izd"/><path class="mjb6-8gcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:generator-20-bold" {...props}></Icon>
