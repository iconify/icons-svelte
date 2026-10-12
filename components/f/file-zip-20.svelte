<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szahujb-p.css';
import '../../css/r/rehf-ikcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="szahujb-p"/><path class="rehf-ikcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-zip-20" {...props}></Icon>
