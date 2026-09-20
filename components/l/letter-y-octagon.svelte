<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw81p4b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw81p4b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-y-octagon" {...props}></Icon>
