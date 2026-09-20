<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf4mjdz4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="cf4mjdz4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:info" {...props}></Icon>
