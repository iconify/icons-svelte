<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwg2ogbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zwg2ogbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grid-dots-duotone" {...props}></Icon>
