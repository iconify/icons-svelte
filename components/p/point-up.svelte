<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qth6jii9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qth6jii9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:point-up" {...props}></Icon>
