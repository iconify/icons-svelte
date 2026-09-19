<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bea-nr_no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="bea-nr_no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-harassing" {...props}></Icon>
