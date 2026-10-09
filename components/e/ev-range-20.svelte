<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjnplr66g.css';
import '../../css/g/gziv7kbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jjnplr66g"/><path class="gziv7kbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-range-20" {...props}></Icon>
