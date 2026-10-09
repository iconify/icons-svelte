<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cco71z33o.css';
import '../../css/i/izilerpqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cco71z33o"/><path class="izilerpqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-pack-20" {...props}></Icon>
