<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puo94vz7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":512};
const content = `<path class="puo94vz7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:gofore" {...props}></Icon>
