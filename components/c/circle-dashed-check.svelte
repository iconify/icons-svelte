<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzblnmbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzblnmbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:circle-dashed-check" {...props}></Icon>
