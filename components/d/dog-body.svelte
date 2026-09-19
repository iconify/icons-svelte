<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh88sjbzq.css';
import '../../css/n/nhpgwyiio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nh88sjbzq"/><path class="nhpgwyiio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dog-body" {...props}></Icon>
