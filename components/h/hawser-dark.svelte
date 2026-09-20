<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pphwdzbsq.css';
import '../../css/j/jxqbrew3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pphwdzbsq"/><path class="jxqbrew3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hawser-dark" {...props}></Icon>
