<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beajqbc6h.css';
import '../../css/g/gfumbbcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beajqbc6h"/><path class="gfumbbcog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:finger-swipe-right-filled" {...props}></Icon>
