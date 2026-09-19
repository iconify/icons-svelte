<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etsqkeb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etsqkeb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:plus-circle-filled" {...props}></Icon>
