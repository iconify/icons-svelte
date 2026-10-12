<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq1olub4s.css';
import '../../css/q/qtnp7cceo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nq1olub4s"/><path class="qtnp7cceo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cat-20-bold" {...props}></Icon>
