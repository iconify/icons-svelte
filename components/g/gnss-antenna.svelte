<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfgrkdb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qfgrkdb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:gnss-antenna" {...props}></Icon>
