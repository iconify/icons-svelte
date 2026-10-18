<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cawzwbo3e.css';
import '../../css/o/o2iujpb6b.css';
import '../../css/f/ftz9zcbou.css';
import '../../css/h/h8v-jytyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cawzwbo3e"/><path class="o2iujpb6b"/><path class="ftz9zcbou"/><path class="h8v-jytyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:net-metering-20" {...props}></Icon>
