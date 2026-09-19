<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhc-nwb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qhc-nwb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:galaxy" {...props}></Icon>
