<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp3lwibtz.css';
import '../../css/m/mdwpa6sgu.css';
import '../../css/u/udgxuob1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lp3lwibtz"/><path class="mdwpa6sgu"/><path class="udgxuob1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:feather-48-bold" {...props}></Icon>
