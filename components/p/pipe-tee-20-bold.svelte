<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl5mofb1p.css';
import '../../css/q/qf_72ga9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nl5mofb1p"/><path class="qf_72ga9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-tee-20-bold" {...props}></Icon>
