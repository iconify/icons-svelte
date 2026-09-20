<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/numv4vb1m.css';
import '../../css/s/snpiwsb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="numv4vb1m"/><circle class="snpiwsb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:orange-circle" {...props}></Icon>
