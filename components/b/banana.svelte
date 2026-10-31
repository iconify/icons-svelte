<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q11bnobfu.css';
import '../../css/l/lec51cbbz.css';
import '../../css/i/ipk8v9b_s.css';
import '../../css/c/cq97wwbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q11bnobfu"/><path class="lec51cbbz"/><path class="ipk8v9b_s"/><path class="cq97wwbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:banana" {...props}></Icon>
