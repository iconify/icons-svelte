<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlva0acsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="tlva0acsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-biking" {...props}></Icon>
