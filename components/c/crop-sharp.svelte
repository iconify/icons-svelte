<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0551ib7x.css';
import '../../css/j/jnf1tabyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u0551ib7x"/><path class="jnf1tabyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:crop-sharp" {...props}></Icon>
