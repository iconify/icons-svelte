<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqu_scb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qqu_scb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:happy2" {...props}></Icon>
