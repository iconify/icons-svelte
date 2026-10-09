<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gihw2lrko.css';
import '../../css/b/brlnqubgb.css';
import '../../css/o/ougbzrbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gihw2lrko"/><path class="brlnqubgb"/><path class="ougbzrbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:meeting-20-bold" {...props}></Icon>
