<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liyswgvjl.css';
import '../../css/o/or_bkw-qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="liyswgvjl"/><path class="or_bkw-qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-right-up-48-bold" {...props}></Icon>
