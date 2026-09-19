<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4cai8-jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z4cai8-jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plus-circle-fill-12" {...props}></Icon>
