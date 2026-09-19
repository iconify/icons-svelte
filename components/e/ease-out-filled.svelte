<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnxgm-9cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnxgm-9cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ease-out-filled" {...props}></Icon>
