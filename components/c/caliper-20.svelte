<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myx735bdk.css';
import '../../css/g/gfw7ev9fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="myx735bdk"/><path class="gfw7ev9fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caliper-20" {...props}></Icon>
