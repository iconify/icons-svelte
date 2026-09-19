<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pma34jxip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pma34jxip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:proper-superset" {...props}></Icon>
