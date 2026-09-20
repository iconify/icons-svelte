<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdzww5_9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wdzww5_9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:amp" {...props}></Icon>
