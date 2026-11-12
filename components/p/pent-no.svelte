<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfc-mjbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfc-mjbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pent-no" {...props}></Icon>
