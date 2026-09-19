<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmsn-19xf.css';
import '../../css/b/beajqbc6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmsn-19xf"/><path class="beajqbc6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:finger-swipe-right" {...props}></Icon>
