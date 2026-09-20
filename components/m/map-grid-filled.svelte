<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opos94p9c.css';
import '../../css/o/o42lp8b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opos94p9c"/><path class="o42lp8b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-grid-filled" {...props}></Icon>
