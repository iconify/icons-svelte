<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q12d-8xco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q12d-8xco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-dashed" {...props}></Icon>
