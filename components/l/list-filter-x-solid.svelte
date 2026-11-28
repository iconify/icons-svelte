<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-2ck6-qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-2ck6-qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-filter-x-solid" {...props}></Icon>
