<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx5vjcz8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx5vjcz8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-fog" {...props}></Icon>
