<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mitqtgtxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mitqtgtxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-down-filled" {...props}></Icon>
