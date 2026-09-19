<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq15jlb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":473,"height":512};
const content = `<path class="nq15jlb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:jison" {...props}></Icon>
