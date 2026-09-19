<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjp21nb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="cjp21nb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-down-short-wide" {...props}></Icon>
