<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe-zdzb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qe-zdzb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:battery" {...props}></Icon>
