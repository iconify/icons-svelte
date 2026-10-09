<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_x1_pbed.css';
import '../../css/s/sf-hyccxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v_x1_pbed"/><path class="sf-hyccxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kettle-20" {...props}></Icon>
