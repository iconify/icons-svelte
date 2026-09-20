<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4cv7lb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g4cv7lb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:mr" {...props}></Icon>
