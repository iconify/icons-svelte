<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5m-7ob2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5m-7ob2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:brick-filled" {...props}></Icon>
