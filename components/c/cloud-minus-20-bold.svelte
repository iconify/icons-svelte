<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvj14fp0a.css';
import '../../css/m/m1vm8ebij.css';
import '../../css/v/vydbu88xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fvj14fp0a"/><path class="m1vm8ebij"/><path class="vydbu88xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-minus-20-bold" {...props}></Icon>
