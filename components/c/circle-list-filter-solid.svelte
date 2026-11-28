<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amj_hoytj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amj_hoytj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-list-filter-solid" {...props}></Icon>
