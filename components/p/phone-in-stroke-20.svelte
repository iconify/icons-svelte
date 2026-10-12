<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d213agn5f.css';
import '../../css/g/gedrdccde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d213agn5f"/><path class="gedrdccde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-in-stroke-20" {...props}></Icon>
