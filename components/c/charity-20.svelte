<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhxatuodl.css';
import '../../css/m/medb0fb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lhxatuodl"/><path class="medb0fb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charity-20" {...props}></Icon>
