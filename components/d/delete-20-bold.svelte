<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-p6gpbin.css';
import '../../css/d/dnun0_bjo.css';
import '../../css/m/mldtn5bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i-p6gpbin"/><path class="dnun0_bjo"/><path class="mldtn5bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:delete-20-bold" {...props}></Icon>
