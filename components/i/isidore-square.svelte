<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fst_4tbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fst_4tbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:isidore-square" {...props}></Icon>
