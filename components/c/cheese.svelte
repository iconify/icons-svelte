<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-ng6m2uq.css';
import '../../css/j/j87piqd4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-ng6m2uq"/><path class="j87piqd4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cheese" {...props}></Icon>
