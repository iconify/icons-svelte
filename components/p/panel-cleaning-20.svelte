<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9p4n1_lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y9p4n1_lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-cleaning-20" {...props}></Icon>
