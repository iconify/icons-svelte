<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdt3zcvtz.css';
import '../../css/s/srn-1hkgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hdt3zcvtz"/><path class="srn-1hkgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:money-bag-48" {...props}></Icon>
