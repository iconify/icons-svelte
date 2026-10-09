<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_fvlabzg.css';
import '../../css/n/nou07ac-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z_fvlabzg"/><path class="nou07ac-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:draught-proofing-20" {...props}></Icon>
